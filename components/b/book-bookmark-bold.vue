<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apdbvacmy.css';
import '../../css/u/u_m41fbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="apdbvacmy"/><path class="u_m41fbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:book-bookmark-bold" /></template>
