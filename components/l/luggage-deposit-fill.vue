<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9vfo9bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9vfo9bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:luggage-deposit-fill" /></template>
