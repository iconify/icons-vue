<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bak9k5bed.css';
import '../../css/t/titlh42pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bak9k5bed"/><path clip-rule="evenodd" class="titlh42pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:explicit-outline" /></template>
