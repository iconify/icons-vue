<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef334u3so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef334u3so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layout" /></template>
