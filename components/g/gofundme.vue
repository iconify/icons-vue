<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfid2qr4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfid2qr4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gofundme" /></template>
