<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q86lr8bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q86lr8bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-o-filled" /></template>
