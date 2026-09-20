<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiv2zubtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiv2zubtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazoneks" /></template>
