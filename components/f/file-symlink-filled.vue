<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crcpm7kfn.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crcpm7kfn"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-symlink-filled" /></template>
