<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snne3jg4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snne3jg4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-button-up-bold" /></template>
