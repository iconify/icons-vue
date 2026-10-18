<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxkobr3yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ban-square-fill" /></template>
<style>
.fxkobr3yk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 6C2 3.7909 3.7909 2 6 2L18 2C20.2091 2 22 3.7909 22 6L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 6ZM6 4.5858C5.8125 4.3983 5.5581 4.2929 5.2929 4.2929C4.7406 4.2929 4.2929 4.7406 4.2929 5.2929C4.2929 5.5581 4.3983 5.8125 4.5858 6L18 19.4142C18.1875 19.6017 18.4419 19.7071 18.7071 19.7071C19.2594 19.7071 19.7071 19.2594 19.7071 18.7071C19.7071 18.4419 19.6017 18.1875 19.4142 18L6 4.5858Z");
}

</style>
