<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yekh7l0nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clear-day-outline" /></template>
<style>
.yekh7l0nz {
  fill: currentColor;
  d: path("M11.5 5.423V2.039h1v3.384zm5.496 2.289l-.682-.683l2.357-2.452l.727.733zm1.581 4.788v-1h3.385v1zM11.5 21.962v-3.366h1v3.366zM7.042 7.68L4.577 5.329l.752-.708L7.73 7.004zm11.624 11.742l-2.352-2.452l.677-.657l2.388 2.346zM2.039 12.5v-1h3.384v1zm3.27 6.923l-.688-.752l2.358-2.357l.36.348l.378.354zm3.153-3.884Q7 14.077 7 12t1.462-3.538T12 7t3.539 1.462T17 12t-1.461 3.539T12 17t-3.538-1.461m6.363-.714Q16 13.65 16 12t-1.175-2.825T12 8T9.175 9.175T8 12t1.175 2.825T12 16t2.825-1.175M12 12");
}

</style>
