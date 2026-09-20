<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf70wobwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf70wobwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bold-24" /></template>
