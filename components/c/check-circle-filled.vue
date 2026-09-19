<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfk5y9bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfk5y9bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:check-circle-filled" /></template>
