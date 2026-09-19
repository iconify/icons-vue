<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4_cu0b4c.css';
import '../../css/f/fvtev__4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4_cu0b4c"/><path class="fvtev__4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevrons-up" /></template>
