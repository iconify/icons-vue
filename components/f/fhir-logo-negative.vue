<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6zxgccaz.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jceynbc9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="healthiconsFhirLogoNegative0" class="d6zxgccaz"/></defs><g class="ft5dv1b6b"><g clip-path="url(#healthiconsFhirLogoNegative1)"><g clip-path="url(#healthiconsFhirLogoNegative2)"><path clip-rule="evenodd" class="jceynbc9n"/></g></g><defs><clipPath id="healthiconsFhirLogoNegative1"><use href="#healthiconsFhirLogoNegative0"/></clipPath><clipPath id="healthiconsFhirLogoNegative2"><use href="#healthiconsFhirLogoNegative0"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:fhir-logo-negative" /></template>
