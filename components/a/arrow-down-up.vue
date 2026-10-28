<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pepvz7i-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pepvz7i-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-up" /></template>
