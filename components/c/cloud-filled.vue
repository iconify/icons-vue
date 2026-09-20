<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r92_c_ckc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r92_c_ckc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-filled" /></template>
