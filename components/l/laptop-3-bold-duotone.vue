<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdvbgrb8q.css';
import '../../css/c/cq7nq2bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdvbgrb8q"/><path class="cq7nq2bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-3-bold-duotone" /></template>
