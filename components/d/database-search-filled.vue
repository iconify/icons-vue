<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohm245beh.css';
import '../../css/e/edfoyo7yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohm245beh"/><path clip-rule="evenodd" class="edfoyo7yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-search-filled" /></template>
