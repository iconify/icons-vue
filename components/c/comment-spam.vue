<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbfryub0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:comment-spam" /></template>
<style>
.jbfryub0h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.279 20.294l.905-3.167q-2.402-3.734-.919-7.991Q4.807 4.708 9.29 3.335t8.241 1.429q3.758 2.804 3.719 7.492q-.001.074-.016.146t-.043.139t-.07.129t-.093.113t-.113.092t-.129.069t-.14.042T20.5 13h-6.25Q13 13 13 14.25v6.25q0 .07-.013.139t-.038.134t-.063.124q-.037.06-.084.111t-.104.093q-.056.042-.119.073t-.13.049t-.138.024q-2.59.214-4.893-.944l-3.212.918q-.071.02-.145.026q-.073.007-.147-.002q-.073-.008-.143-.031q-.071-.023-.135-.058t-.121-.084q-.056-.048-.102-.106t-.08-.123t-.054-.137q-.059-.206 0-.412M18 14.25q-3.75 0-3.75 3.75T18 21.75T21.75 18T18 14.25");
}

</style>
