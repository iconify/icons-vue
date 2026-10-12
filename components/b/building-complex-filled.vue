<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6j4wovga.css';
import '../../css/g/gcy3r1rbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6j4wovga"/><path class="gcy3r1rbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:building-complex-filled" /></template>
