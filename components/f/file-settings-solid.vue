<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vknv7fbam.css';
import '../../css/c/cbjx-lv-q.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 vknv7fbam"/><path class="cbjx-lv-q clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:file-settings-solid" /></template>
