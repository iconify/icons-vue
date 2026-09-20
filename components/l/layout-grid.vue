<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ykeibmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4ykeibmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-grid" /></template>
