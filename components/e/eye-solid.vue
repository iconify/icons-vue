<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9bk5cbdt.css';
import '../../css/k/k2_62w1sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9bk5cbdt"/><path class="k2_62w1sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:eye-solid" /></template>
