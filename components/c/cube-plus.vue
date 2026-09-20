<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9140c1rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9140c1rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cube-plus" /></template>
