<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf60hrb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nf60hrb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-right-circle" /></template>
