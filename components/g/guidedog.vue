<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0wu_68ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="x0wu_68ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:guidedog" /></template>
