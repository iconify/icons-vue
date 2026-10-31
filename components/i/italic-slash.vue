<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2j_-ibse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2j_-ibse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:italic-slash" /></template>
