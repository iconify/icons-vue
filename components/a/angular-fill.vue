<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpxx19b4u.css';
import '../../css/b/bq2iq2bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpxx19b4u"/><path class="bq2iq2bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:angular-fill" /></template>
