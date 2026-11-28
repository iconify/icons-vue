<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_ykcp1sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ykcp1sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gift-star" /></template>
