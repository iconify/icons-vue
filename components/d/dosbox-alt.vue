<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owkcs8bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":456,"height":512};
const content = `<path clip-rule="evenodd" class="owkcs8bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dosbox-alt" /></template>
