<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubq-_mz2b.css';
import '../../css/s/sbqm2wbdh.css';
import '../../css/e/eh56eccoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubq-_mz2b"/><circle class="sbqm2wbdh"/><circle class="eh56eccoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bus" /></template>
