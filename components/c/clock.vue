<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqbayhb7u.css';
import '../../css/v/v8kcivbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqbayhb7u"/><path class="v8kcivbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:clock" /></template>
