<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da9m5rt6q.css';
import '../../css/e/e3kxkcb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da9m5rt6q"/><path class="e3kxkcb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:circle-dot-duotone" /></template>
