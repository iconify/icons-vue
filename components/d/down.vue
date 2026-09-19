<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz-t35b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":392,"height":448};
const content = `<path class="sz-t35b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:down" /></template>
