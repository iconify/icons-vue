<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvve5bzij.css';
import '../../css/u/u9ixn_sru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvve5bzij"/><path class="u9ixn_sru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:device-mobile-24" /></template>
