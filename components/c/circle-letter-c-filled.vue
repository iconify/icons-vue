<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj9ymybmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj9ymybmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-c-filled" /></template>
