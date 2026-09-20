<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmy8lab0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bmy8lab0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horseshoe-with-stake" /></template>
