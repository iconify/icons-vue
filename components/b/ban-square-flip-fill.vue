<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3v13m3xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ban-square-flip-fill" /></template>
<style>
.y3v13m3xi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 6C22 3.7909 20.2091 2 18 2L6 2C3.7909 2 2 3.7909 2 6L2 18C2 20.2091 3.7909 22 6 22L18 22C20.2091 22 22 20.2091 22 18L22 6ZM18 4.5858C18.1875 4.3983 18.4419 4.2929 18.7071 4.2929C19.2594 4.2929 19.7071 4.7406 19.7071 5.2929C19.7071 5.5581 19.6017 5.8125 19.4142 6L6 19.4142C5.8125 19.6017 5.5581 19.7071 5.2929 19.7071C4.7406 19.7071 4.2929 19.2594 4.2929 18.7071C4.2929 18.4419 4.3983 18.1875 4.5858 18L18 4.5858Z");
}

</style>
