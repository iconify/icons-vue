<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkr6uybsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkr6uybsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:align-alt" /></template>
