<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6e9n0bgt.css';
import '../../css/q/qcetc5ipd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6e9n0bgt"/><path clip-rule="evenodd" class="qcetc5ipd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-down-filled" /></template>
