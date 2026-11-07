<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb59sp9du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb59sp9du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-broken" /></template>
