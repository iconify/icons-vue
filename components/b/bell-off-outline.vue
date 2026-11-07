<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewr0bdyvc.css';
import '../../css/l/ll7areqdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewr0bdyvc"/><path clip-rule="evenodd" class="ll7areqdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-off-outline" /></template>
