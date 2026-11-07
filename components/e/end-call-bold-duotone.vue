<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfwi7necl.css';
import '../../css/b/bohfcinem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfwi7necl"/><path class="bohfcinem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-bold-duotone" /></template>
