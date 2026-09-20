<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwe21bdcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwe21bdcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-bulma" /></template>
