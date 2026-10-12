<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjmxtcbsh.css';
import '../../css/f/f4-u1zbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjmxtcbsh"/><path class="f4-u1zbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-minus-corner-filled" /></template>
