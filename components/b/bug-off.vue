<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/savd2lv8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="savd2lv8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bug-off" /></template>
