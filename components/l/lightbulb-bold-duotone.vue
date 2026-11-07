<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1j0ccckq.css';
import '../../css/b/bdli7f47j.css';
import '../../css/x/xe1ahotxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1j0ccckq"/><path class="bdli7f47j"/><path class="xe1ahotxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightbulb-bold-duotone" /></template>
