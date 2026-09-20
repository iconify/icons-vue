<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee3miprbq.css';
import '../../css/g/gnsu0ijom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee3miprbq"/><path class="gnsu0ijom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:inbox-plus-fill" /></template>
