<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s75wz-bud.css';
import '../../css/o/o6fe24b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s75wz-bud"/><path class="o6fe24b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-from-line-bold-duotone" /></template>
