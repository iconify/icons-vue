<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0fx9dk3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-link-24-regular" /></template>
<style>
.e0fx9dk3g {
  fill: currentColor;
  d: path("M9.629 6.33a8.376 8.376 0 0 1 5.596 14.29l-.001-.002l-.927.929a3.25 3.25 0 0 1-4.598 0l-7.247-7.25a3.25 3.25 0 0 1 0-4.596l.929-.927a8.4 8.4 0 0 1 2.18-1.57a9.4 9.4 0 0 0-.235 1.885q-.466.33-.885.746l-.928.927a1.75 1.75 0 0 0 0 2.475l7.247 7.25a1.75 1.75 0 0 0 2.475 0l.93-.93A6.876 6.876 0 0 0 9.01 7.829c.134-.52.34-1.025.619-1.499m.07-3.876a3.25 3.25 0 0 1 4.597-.002l7.248 7.25a3.25 3.25 0 0 1-.001 4.597l-.93.928a8.4 8.4 0 0 1-2.17 1.565a9.4 9.4 0 0 0 .233-1.886q.462-.328.877-.74l.93-.928a1.75 1.75 0 0 0 0-2.475l-7.248-7.25a1.75 1.75 0 0 0-2.475 0l-.93.93a6.876 6.876 0 0 0 5.162 11.729a5.8 5.8 0 0 1-.619 1.5A8.375 8.375 0 0 1 8.77 3.382z");
}

</style>
