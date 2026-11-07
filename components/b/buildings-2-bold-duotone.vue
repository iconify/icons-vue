<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8ld33dpy.css';
import '../../css/x/x7pqpmbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8ld33dpy"/><path clip-rule="evenodd" class="x7pqpmbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-2-bold-duotone" /></template>
