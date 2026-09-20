<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv36f1m1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv36f1m1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:emergency-stop-filled" /></template>
