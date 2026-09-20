<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmd6kxe2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmd6kxe2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:calendar-minus-solid" /></template>
