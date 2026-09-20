<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vifuy2dbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vifuy2dbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:flash2-filled" /></template>
