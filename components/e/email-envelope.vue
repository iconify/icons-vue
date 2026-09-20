<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imlqtwr-v.css';
import '../../css/b/bmvaj0s_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="imlqtwr-v"/><path class="bmvaj0s_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-envelope" /></template>
