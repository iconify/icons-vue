<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kma6xtbjg.css';
import '../../css/d/dewcoqb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kma6xtbjg"/><path class="dewcoqb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magic-stick-bold-duotone" /></template>
