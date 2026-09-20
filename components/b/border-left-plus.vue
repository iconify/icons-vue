<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugfsqiunw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugfsqiunw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:border-left-plus" /></template>
