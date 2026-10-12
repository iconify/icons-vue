<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy37fwx1z.css';
import '../../css/a/aqrtcbb7a.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qy37fwx1z"/><path class="aqrtcbb7a"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-box-filled" /></template>
