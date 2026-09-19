<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueby7ebgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ueby7ebgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:common-lisp" /></template>
