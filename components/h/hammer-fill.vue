<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7y4svbea.css';
import '../../css/o/o2549tb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7y4svbea"/><path class="o2549tb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hammer-fill" /></template>
