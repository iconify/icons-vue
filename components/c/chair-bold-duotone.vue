<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln-p1pbos.css';
import '../../css/p/p8jcaxb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln-p1pbos"/><path class="p8jcaxb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chair-bold-duotone" /></template>
