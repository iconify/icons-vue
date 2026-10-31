<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxlvi1bje.css';
import '../../css/r/r9m45djyc.css';
import '../../css/m/mempy7bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="xxlvi1bje"/><path class="r9m45djyc"/><path class="mempy7bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:czechia" /></template>
