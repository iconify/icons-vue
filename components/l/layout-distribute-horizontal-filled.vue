<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsnrkh4ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsnrkh4ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-distribute-horizontal-filled" /></template>
