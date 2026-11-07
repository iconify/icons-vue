<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7-5n80rg.css';
import '../../css/l/leb-08bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7-5n80rg"/><path class="leb-08bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-down-up-bold" /></template>
