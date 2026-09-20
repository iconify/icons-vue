<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sslb1u9_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sslb1u9_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:fire" /></template>
