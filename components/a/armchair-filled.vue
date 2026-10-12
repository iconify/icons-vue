<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt_t72bdg.css';
import '../../css/e/ej2tdcg6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt_t72bdg"/><path class="ej2tdcg6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:armchair-filled" /></template>
