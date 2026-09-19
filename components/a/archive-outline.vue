<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiz8lpbui.css';
import '../../css/i/iufc13bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiz8lpbui"/><rect class="iufc13bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:archive-outline" /></template>
