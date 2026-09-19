<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oonu74b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oonu74b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:gender-female" /></template>
