<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkvl0ybhw.css';
import '../../css/q/qosnnxx8l.css';
import '../../css/x/x41xvfi0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkvl0ybhw"/><path class="qosnnxx8l"/><path class="x41xvfi0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-triangle-bold-duotone" /></template>
