<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j00ef2i9a.css';
import '../../css/v/vje10cmgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j00ef2i9a"/><path class="vje10cmgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:activity-filled" /></template>
