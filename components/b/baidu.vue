<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1ll4_eeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c1ll4_eeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:baidu" /></template>
