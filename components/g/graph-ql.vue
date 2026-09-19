<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhb3vsb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhb3vsb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:graph-ql" /></template>
