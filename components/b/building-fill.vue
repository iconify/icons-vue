<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7wtl-18m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:building-fill" /></template>
<style>
.v7wtl-18m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1H17C19.20914 1 21 2.79086 21 5V19C21 21.20914 19.20914 23 17 23H15V20C15 18.34315 13.65685 17 12 17C10.34315 17 9 18.34315 9 20V23H7C4.79086 23 3 21.20914 3 19V5C3 2.79086 4.79086 1 7 1ZM9 5C8.44772 5 8 5.44772 8 6V8C8 8.55228 8.44772 9 9 9C9.55228 9 10 8.55228 10 8V6C10 5.44772 9.55228 5 9 5ZM15 5C14.44772 5 14 5.44772 14 6V8C14 8.55228 14.44772 9 15 9C15.55228 9 16 8.55228 16 8V6C16 5.44772 15.55228 5 15 5ZM9 11C8.44772 11 8 11.44772 8 12V14C8 14.55228 8.44772 15 9 15C9.55228 15 10 14.55228 10 14V12C10 11.44772 9.55228 11 9 11ZM15 11C14.44772 11 14 11.44772 14 12V14C14 14.55228 14.44772 15 15 15C15.55228 15 16 14.55228 16 14V12C16 11.44772 15.55228 11 15 11Z");
}

</style>
