<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k2wzvwbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-add-16-filled" /></template>
<style>
.k2wzvwbsv {
  fill: currentColor;
  d: path("M9.75 3h.516a3.74 3.74 0 0 1 3.731 3.598a5.5 5.5 0 0 0-1.6-.525a2.24 2.24 0 0 0-1.978-1.568l-.153-.005H9.75a.75.75 0 0 1-.102-1.493zm-3.66 7.505a5.5 5.5 0 0 1 .473-1.432a.75.75 0 0 0-.313-.068h-.498l-.154-.006A2.252 2.252 0 0 1 5.752 4.5h.498l.102-.007A.75.75 0 0 0 6.25 3h-.498l-.199.005a3.752 3.752 0 0 0 .2 7.5zM7.725 7.5a5.5 5.5 0 0 1 2.855-1.423a.75.75 0 0 0-.33-.077h-4.5l-.102.007A.75.75 0 0 0 5.75 7.5zm8.275 4a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12z");
}

</style>
