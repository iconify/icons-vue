<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncfs9ob1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncfs9ob1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:credit-card-alt" /></template>
