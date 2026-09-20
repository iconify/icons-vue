<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3bjr7btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k3bjr7btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-type-enhancement" /></template>
