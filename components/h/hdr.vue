<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abh8sfbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abh8sfbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hdr" /></template>
