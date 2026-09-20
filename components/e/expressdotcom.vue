<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9zg3hbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9zg3hbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:expressdotcom" /></template>
