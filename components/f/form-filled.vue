<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxh_a9ajg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxh_a9ajg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:form-filled" /></template>
