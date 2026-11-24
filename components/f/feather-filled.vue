<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cve7h0b7y.css';
import '../../css/r/rb36fjzyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cve7h0b7y"/><path class="rb36fjzyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:feather-filled" /></template>
