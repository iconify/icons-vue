<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8fzu_bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8fzu_bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrows-reload-01" /></template>
