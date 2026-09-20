<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofhn5rwuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofhn5rwuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:highlight" /></template>
