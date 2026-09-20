<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh_rwbkdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh_rwbkdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-x" /></template>
