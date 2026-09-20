<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb6i929xq.css';
import '../../css/i/iea0nmbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb6i929xq"/><path class="iea0nmbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:first-aid-kit-fill" /></template>
