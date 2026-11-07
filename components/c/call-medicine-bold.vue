<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/encu70b2r.css';
import '../../css/p/pkhtqxbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="encu70b2r"/><path clip-rule="evenodd" class="pkhtqxbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-medicine-bold" /></template>
