<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq2hqvwyz.css';
import '../../css/b/b9htj9b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq2hqvwyz"/><path class="b9htj9b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-output-bold-duotone" /></template>
