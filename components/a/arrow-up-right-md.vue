<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzt9n_bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzt9n_bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-up-right-md" /></template>
