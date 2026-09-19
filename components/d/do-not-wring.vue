<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csk2dwbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":512};
const content = `<path class="csk2dwbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:do-not-wring" /></template>
