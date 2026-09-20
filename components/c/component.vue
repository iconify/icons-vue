<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":257};
const content = `<path class="na9czwcpi"/><path class="whsd0abbw"/><path class="xnj2x4jmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:component" /></template>
<style>
.na9czwcpi {
  d: path("M214.57 131.72c0 17.483-5.186 33.736-14.018 47.405l29.51 26.24c16.16-21.421 25.859-47.992 25.859-76.896c0-28.742-9.593-55.181-25.597-76.546l-32.262 28.78c10.342 14.374 16.509 31.956 16.509 51.018");
  fill: var(--svg-color--7a797a, #7A797A);
}

.whsd0abbw {
  d: path("M196.102 185.36c-16.016 20.579-40.95 33.873-69.044 33.873c-48.334 0-87.512-39.184-87.512-87.512c0-48.335 39.178-87.513 87.512-87.513c26.527 0 50.245 11.847 66.292 30.49l32.28-28.792C202.164 18.169 167.142.518 127.97.518C57.303.518.018 57.802.018 128.468c0 70.667 57.285 127.952 127.952 127.952c39.022 0 73.9-17.52 97.367-45.064l-29.235-25.996");
  fill: var(--svg-color--343334, #343334);
}

.xnj2x4jmy {
  d: path("M162.491 132.626c0 19.623-15.91 35.533-35.533 35.533c-19.63 0-35.533-15.91-35.533-35.533c0-19.63 15.904-35.533 35.533-35.533c19.624 0 35.533 15.903 35.533 35.533");
  fill: var(--svg-color--474547, #474547);
}

</style>
