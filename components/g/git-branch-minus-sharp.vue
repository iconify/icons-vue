<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdhqldb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdhqldb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-branch-minus-sharp" /></template>
