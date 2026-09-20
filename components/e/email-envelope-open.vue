<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqc-2tjjs.css';
import '../../css/i/ix9txabgz.css';
import '../../css/o/opf7hobje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kqc-2tjjs"/><path class="ix9txabgz"/><path class="opf7hobje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-envelope-open" /></template>
