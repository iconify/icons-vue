<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojhdz2bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojhdz2bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-minus-sharp-fill" /></template>
