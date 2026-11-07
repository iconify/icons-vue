<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-klr3bdo.css';
import '../../css/e/e8icw_b4f.css';
import '../../css/w/ws9d_1b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-klr3bdo"/><path class="e8icw_b4f"/><path clip-rule="evenodd" class="ws9d_1b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:car-outline" /></template>
