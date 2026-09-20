<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs-8h9bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs-8h9bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:envato" /></template>
