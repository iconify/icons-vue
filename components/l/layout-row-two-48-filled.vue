<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="um6w65bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-48-filled" /></template>
<style>
.um6w65bpo {
  fill: currentColor;
  d: path("M12.25 6A6.25 6.25 0 0 0 6 12.25v10.5h36v-10.5A6.25 6.25 0 0 0 35.75 6zM42 25.25H6v10.5A6.25 6.25 0 0 0 12.25 42h23.5A6.25 6.25 0 0 0 42 35.75z");
}

</style>
