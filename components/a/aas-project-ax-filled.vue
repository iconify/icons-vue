<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3cvc_b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3cvc_b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-project-ax-filled" /></template>
