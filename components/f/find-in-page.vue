<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akonkacqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akonkacqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:find-in-page" /></template>
