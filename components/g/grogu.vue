<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l925n1bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l925n1bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:grogu" /></template>
