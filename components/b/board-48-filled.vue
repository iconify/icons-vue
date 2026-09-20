<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xiuoayboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:board-48-filled" /></template>
<style>
.xiuoayboh {
  fill: currentColor;
  d: path("M23 42H12.25A6.25 6.25 0 0 1 6 35.75V19.5h17zm19-6.25A6.25 6.25 0 0 1 35.75 42H25.5V31H42zM35.75 6A6.25 6.25 0 0 1 42 12.25V28.5H25.5V6zM23 17H6v-4.75A6.25 6.25 0 0 1 12.25 6H23z");
}

</style>
