<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3c-5acjg.css';
import '../../css/g/g5wxtpvfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3c-5acjg"/><path class="g5wxtpvfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layers-arrow-down-filled" /></template>
