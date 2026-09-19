<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3cw8xeca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3cw8xeca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bug-filled" /></template>
