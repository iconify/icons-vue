<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk69bcc_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk69bcc_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cope" /></template>
