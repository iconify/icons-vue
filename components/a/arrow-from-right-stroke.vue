<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euem3vl2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euem3vl2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-from-right-stroke" /></template>
