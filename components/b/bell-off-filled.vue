<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tykflebtg.css';
import '../../css/c/cfkeagz0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tykflebtg"/><path class="cfkeagz0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-off-filled" /></template>
