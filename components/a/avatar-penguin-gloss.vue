<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etjt0qrff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etjt0qrff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-penguin-gloss" /></template>
